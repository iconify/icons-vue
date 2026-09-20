<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-v_mj_8z.css';
import '../../css/v/v4evbjbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-v_mj_8z"/><path class="v4evbjbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:monetize-duotone" /></template>
