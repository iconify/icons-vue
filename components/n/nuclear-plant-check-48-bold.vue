<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1_s4oue.css';
import '../../css/a/a-1g_ibpd.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vi1_s4oue"/><path class="a-1g_ibpd"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-plant-check-48-bold" /></template>
