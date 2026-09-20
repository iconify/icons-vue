<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw0v5yb-n.css';
import '../../css/f/f9b-7_qnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw0v5yb-n"/><path class="f9b-7_qnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-duotone" /></template>
