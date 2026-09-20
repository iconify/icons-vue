<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsbtvljfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jsbtvljfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-carrying-skis-and-ski-poles" /></template>
