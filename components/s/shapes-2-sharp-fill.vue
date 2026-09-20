<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4nuqs5iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4nuqs5iq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-2-sharp-fill" /></template>
