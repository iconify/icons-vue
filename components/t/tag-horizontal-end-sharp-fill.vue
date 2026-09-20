<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_erbb58d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_erbb58d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-end-sharp-fill" /></template>
