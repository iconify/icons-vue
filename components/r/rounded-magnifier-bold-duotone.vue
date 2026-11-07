<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9y477w0i.css';
import '../../css/o/ov-0mlbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="ov-0mlbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-bold-duotone" /></template>
