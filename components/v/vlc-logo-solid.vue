<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukk6o2w9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ukk6o2w9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:vlc-logo-solid" /></template>
