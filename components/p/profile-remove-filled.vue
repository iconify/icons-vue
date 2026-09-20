<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la38wybmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la38wybmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:profile-remove-filled" /></template>
