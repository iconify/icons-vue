<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za0456b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="za0456b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-alert-sharp-fill" /></template>
