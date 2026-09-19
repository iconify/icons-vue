<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipt8wobsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="ipt8wobsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:radiobutton" /></template>
