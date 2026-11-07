<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd99cys7x.css';
import '../../css/y/y00wue9pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd99cys7x"/><path class="y00wue9pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plain-2-bold" /></template>
