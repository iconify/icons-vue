<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgrcozv4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgrcozv4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:mic-light" /></template>
