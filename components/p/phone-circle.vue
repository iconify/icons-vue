<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge5bw_bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ge5bw_bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-circle" /></template>
