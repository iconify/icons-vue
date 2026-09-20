<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf3k0wf1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf3k0wf1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wireless-charge-outline" /></template>
