<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzu_v_-nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzu_v_-nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wallabag-light" /></template>
