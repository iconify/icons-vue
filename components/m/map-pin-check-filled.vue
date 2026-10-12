<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_vsq7l3i.css';
import '../../css/a/auwtx0yen.css';
import '../../css/z/zthldachh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_vsq7l3i"/><path clip-rule="evenodd" class="auwtx0yen"/><path class="zthldachh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-check-filled" /></template>
