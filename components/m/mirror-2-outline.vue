<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahe6_mtbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ahe6_mtbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-2-outline" /></template>
