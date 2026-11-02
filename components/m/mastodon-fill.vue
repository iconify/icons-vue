<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk3jx7dit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk3jx7dit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mastodon-fill" /></template>
