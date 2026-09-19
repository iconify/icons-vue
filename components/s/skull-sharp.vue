<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsh4tibvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wsh4tibvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:skull-sharp" /></template>
