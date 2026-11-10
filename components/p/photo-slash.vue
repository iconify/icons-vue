<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6nt4dr_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6nt4dr_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:photo-slash" /></template>
