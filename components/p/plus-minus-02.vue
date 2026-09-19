<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b500ppqck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b500ppqck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plus-minus-02" /></template>
