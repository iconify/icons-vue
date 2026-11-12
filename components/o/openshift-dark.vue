<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdh71-7os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gdh71-7os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openshift-dark" /></template>
