<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwt8ei2ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rwt8ei2ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:plug-slash-16-solid" /></template>
