<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be7rzowhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be7rzowhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-minus" /></template>
