<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht_mu-b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ht_mu-b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:umbrella-outline" /></template>
