<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-5jq9bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-5jq9bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:rsync" /></template>
