<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1u5wbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ii1u5wbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextdoor-light" /></template>
