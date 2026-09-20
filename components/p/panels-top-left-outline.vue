<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acs2urb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="acs2urb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-left-outline" /></template>
