<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibr21gb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibr21gb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:property-edit" /></template>
