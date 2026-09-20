<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvxyueb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvxyueb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings-dot-sharp-fill" /></template>
