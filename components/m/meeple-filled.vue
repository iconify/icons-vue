<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljcwlzb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljcwlzb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:meeple-filled" /></template>
