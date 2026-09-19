<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duuf9m24f.css';
import '../../css/g/gj0wcwb7j.css';
import '../../css/y/ym_5dj0al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="duuf9m24f"/><path class="gj0wcwb7j"/><path class="ym_5dj0al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:wifi-fill" /></template>
