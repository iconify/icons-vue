<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4te_bdvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4te_bdvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-x-filled" /></template>
