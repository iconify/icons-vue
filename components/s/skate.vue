<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwnv5sbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pwnv5sbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:skate" /></template>
