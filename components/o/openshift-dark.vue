<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3bpygbod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3bpygbod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openshift-dark" /></template>
