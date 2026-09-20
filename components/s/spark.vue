<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6hue7bl.css';
import '../../css/h/h50klb51r.css';
import '../../css/q/q9pd_y20i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt6hue7bl"/><path class="h50klb51r"/><path clip-rule="evenodd" class="q9pd_y20i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spark" /></template>
