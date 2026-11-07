<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyt4yhbtg.css';
import '../../css/p/p4ej_wfwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyt4yhbtg"/><path class="p4ej_wfwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-bold-duotone" /></template>
