<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q615-bq5v.css';
import '../../css/k/k-og-_b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q615-bq5v"/><circle class="k-og-_b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rimgo-light" /></template>
