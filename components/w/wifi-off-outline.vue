<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duuf9m24f.css';
import '../../css/h/h8p6cfbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="duuf9m24f"/><path class="h8p6cfbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:wifi-off-outline" /></template>
