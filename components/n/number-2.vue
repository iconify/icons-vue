<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1l0m8bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1l0m8bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-2" /></template>
