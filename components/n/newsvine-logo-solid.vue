<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmwyj3bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmwyj3bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:newsvine-logo-solid" /></template>
