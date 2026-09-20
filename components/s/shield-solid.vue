<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8rvxhcni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s8rvxhcni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shield-solid" /></template>
