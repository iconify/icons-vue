<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha685db6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ha685db6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:password-16-solid" /></template>
