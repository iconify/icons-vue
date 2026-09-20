<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx8quie_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx8quie_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:vertical-distribute-bottom" /></template>
