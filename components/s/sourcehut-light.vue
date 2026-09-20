<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glrftzbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glrftzbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sourcehut-light" /></template>
