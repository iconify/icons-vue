<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwn8xtore.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwn8xtore"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play-btn-solid" /></template>
