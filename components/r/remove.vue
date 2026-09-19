<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq3c7540h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq3c7540h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:remove" /></template>
