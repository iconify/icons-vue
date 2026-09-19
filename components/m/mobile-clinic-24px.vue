<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk5vftbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pk5vftbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mobile-clinic-24px" /></template>
