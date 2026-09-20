<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhsc1vb_v.css';
import '../../css/w/wpob71b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dhsc1vb_v"/><path class="wpob71b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:netbox" /></template>
