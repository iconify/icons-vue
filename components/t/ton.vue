<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ri238lb_r.css';
import '../../css/p/pkupc97st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<g class="ft5dv1b6b"><path class="ri238lb_r"/><path class="pkupc97st"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ton" /></template>
