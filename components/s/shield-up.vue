<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocri5bbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocri5bbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-up" /></template>
