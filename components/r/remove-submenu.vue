<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwqd-kc1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="nwqd-kc1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:remove-submenu" /></template>
