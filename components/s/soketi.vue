<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it6b2o5on.css';
import '../../css/z/znj3s6bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1314.4,"height":1314.4,"left":340.8,"top":342.8};
const content = `<path class="it6b2o5on"/><path class="znj3s6bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:soketi" /></template>
