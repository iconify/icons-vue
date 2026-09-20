<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3fpsd3sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o3fpsd3sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openshift-light" /></template>
