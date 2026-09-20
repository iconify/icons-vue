<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agzpq5bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="agzpq5bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plaaylist-minimalistic-outline" /></template>
