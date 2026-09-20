<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvxw2nvec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvxw2nvec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-plus-sharp-fill" /></template>
