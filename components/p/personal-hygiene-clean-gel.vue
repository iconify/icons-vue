<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozo2onbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozo2onbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:personal-hygiene-clean-gel" /></template>
