<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx9irdq5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gx9irdq5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:nswitch" /></template>
