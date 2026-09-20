<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g508y9_og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g508y9_og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:mastodon-logo-2-block" /></template>
