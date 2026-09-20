<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6yhmq1dy.css';
import '../../css/b/bc3db-fby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yhmq1dy"/><path class="bc3db-fby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-cog-duotone" /></template>
