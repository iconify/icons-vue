<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df8smc1yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df8smc1yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-filled" /></template>
