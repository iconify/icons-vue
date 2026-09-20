<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iig0ngsil.css';
import '../../css/f/f3oom5dbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iig0ngsil"/><path class="f3oom5dbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:save-ribbon-duotone" /></template>
