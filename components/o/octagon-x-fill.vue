<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn5gkh4pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn5gkh4pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-x-fill" /></template>
