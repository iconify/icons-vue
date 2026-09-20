<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaee-kl8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaee-kl8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:share" /></template>
