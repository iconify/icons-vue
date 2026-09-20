<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zabbtyb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zabbtyb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:three-dots-left-right-in-wide-rounded-rectangle" /></template>
