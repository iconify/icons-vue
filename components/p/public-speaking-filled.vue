<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6y9utx6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6y9utx6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:public-speaking-filled" /></template>
