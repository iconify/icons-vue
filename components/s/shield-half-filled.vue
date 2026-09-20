<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s63tnf0jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s63tnf0jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-half-filled" /></template>
