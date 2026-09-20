<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6v55xb4m.css';
import '../../css/h/h3e8qmb6x.css';
import '../../css/m/mpmb-4bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21,"left":1.5,"top":1.5};
const content = `<path class="x6v55xb4m"/><circle class="h3e8qmb6x"/><path class="mpmb-4bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wacheit" /></template>
