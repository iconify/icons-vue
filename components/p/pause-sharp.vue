<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9nkwub_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9nkwub_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pause-sharp" /></template>
