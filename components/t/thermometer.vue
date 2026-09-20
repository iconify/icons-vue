<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfbx6odob.css';
import '../../css/r/r7sd-ibvw.css';
import '../../css/h/hrqt4gbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="jfbx6odob"/><circle class="r7sd-ibvw"/><path class="hrqt4gbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:thermometer" /></template>
