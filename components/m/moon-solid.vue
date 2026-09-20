<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw_0fyb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fw_0fyb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:moon-solid" /></template>
