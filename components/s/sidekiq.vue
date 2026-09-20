<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut3hye_bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3hye_bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sidekiq" /></template>
