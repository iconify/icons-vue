<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp7vij--s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bp7vij--s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:steam-logo-block" /></template>
