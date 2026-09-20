<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erw8smbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erw8smbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:text-outline" /></template>
