<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajpmlpmwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajpmlpmwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openemr-light" /></template>
