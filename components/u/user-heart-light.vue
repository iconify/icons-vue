<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plkxy1bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plkxy1bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-heart-light" /></template>
