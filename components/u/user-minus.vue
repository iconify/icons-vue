<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo9fkpbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo9fkpbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-minus" /></template>
