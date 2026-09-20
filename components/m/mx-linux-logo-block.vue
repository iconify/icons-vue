<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw4q79iux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw4q79iux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mx-linux-logo-block" /></template>
