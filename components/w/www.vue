<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewvl3nb8h.css';
import '../../css/v/vn8vinb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewvl3nb8h"/><path clip-rule="evenodd" class="vn8vinb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:www" /></template>
