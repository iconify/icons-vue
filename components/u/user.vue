<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjr12o5iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjr12o5iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:user" /></template>
