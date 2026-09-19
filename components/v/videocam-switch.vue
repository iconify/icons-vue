<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgw1eqx5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="rgw1eqx5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:videocam-switch" /></template>
