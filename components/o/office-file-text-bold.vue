<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zemhzbc5a.css';
import '../../css/r/r6fwiknyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zemhzbc5a"/><path class="r6fwiknyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-file-text-bold" /></template>
