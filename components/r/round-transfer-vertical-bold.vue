<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suaf7nfwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="suaf7nfwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-vertical-bold" /></template>
