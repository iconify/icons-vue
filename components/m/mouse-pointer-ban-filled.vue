<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juq__jbid.css';
import '../../css/j/jkbt_jb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="juq__jbid"/><path class="jkbt_jb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mouse-pointer-ban-filled" /></template>
