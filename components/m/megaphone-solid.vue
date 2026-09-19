<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hulx-ksmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hulx-ksmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:megaphone-solid" /></template>
