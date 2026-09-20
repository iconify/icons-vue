<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np_tewe7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np_tewe7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rocksdb" /></template>
