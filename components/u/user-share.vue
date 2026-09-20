<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq7dm-fht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq7dm-fht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-share" /></template>
