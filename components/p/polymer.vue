<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prkc-3yml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":384};
const content = `<path class="prkc-3yml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:polymer" /></template>
