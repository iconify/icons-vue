<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf4hgk1ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4hgk1ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-up" /></template>
