<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzfdldm6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzfdldm6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:re-director-dark" /></template>
