<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe0m34kxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pe0m34kxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plain-3-outline" /></template>
