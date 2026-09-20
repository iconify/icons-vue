<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap81if3yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ap81if3yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:salesforce" /></template>
