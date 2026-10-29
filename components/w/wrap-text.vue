<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqdrapcbo.css';
import '../../css/m/m25ry3gfk.css';
import '../../css/h/hdamidbnm.css';
import '../../css/s/six1ttbia.css';
import '../../css/u/uyzcbshul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqdrapcbo wm-shadow"/><path class="m25ry3gfk wm-k"/><path class="hdamidbnm wm-k"/><path class="six1ttbia wm-a"/><path class="uyzcbshul wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:wrap-text" /></template>
