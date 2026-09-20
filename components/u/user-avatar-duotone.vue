<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5v__0v2h.css';
import '../../css/y/y6k8bq-ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5v__0v2h"/><path class="y6k8bq-ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:user-avatar-duotone" /></template>
