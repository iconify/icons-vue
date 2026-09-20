<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8luf4olm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k8luf4olm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wigwam-light" /></template>
