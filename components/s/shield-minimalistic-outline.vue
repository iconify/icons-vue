<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lns7h3qht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lns7h3qht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-outline" /></template>
