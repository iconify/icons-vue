<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozaoy9b0z.css';
import '../../css/o/oazgwdbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozaoy9b0z"/><path class="oazgwdbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-hands-bold" /></template>
