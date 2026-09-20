<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75wlqz3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q75wlqz3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-arrow-down-light" /></template>
