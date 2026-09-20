<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_nd3rw4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_nd3rw4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-letter-o-filled" /></template>
