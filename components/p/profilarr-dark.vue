<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk1ci18po.css';
import '../../css/j/jwjgdy4tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mk1ci18po"/><path class="jwjgdy4tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:profilarr-dark" /></template>
