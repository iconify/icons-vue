<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a024-dbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a024-dbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:stop-fill" /></template>
