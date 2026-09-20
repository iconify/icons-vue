<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-1l42bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-1l42bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peer-calls-light" /></template>
