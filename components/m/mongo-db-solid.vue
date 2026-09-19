<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krq7gibqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="krq7gibqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mongo-db-solid" /></template>
