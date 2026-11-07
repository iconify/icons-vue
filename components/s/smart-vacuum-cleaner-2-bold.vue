<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0cyhdctz.css';
import '../../css/n/nda3cdcdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0cyhdctz"/><path clip-rule="evenodd" class="nda3cdcdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-vacuum-cleaner-2-bold" /></template>
