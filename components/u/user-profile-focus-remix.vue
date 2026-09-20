<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z45lxu-fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z45lxu-fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-profile-focus-remix" /></template>
