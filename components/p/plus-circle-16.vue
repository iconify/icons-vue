<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn_x7fxrw.css';
import '../../css/h/hozw9riwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sn_x7fxrw"/><path class="hozw9riwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plus-circle-16" /></template>
