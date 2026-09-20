<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m11n33b9i.css';
import '../../css/x/xt5xc0eya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m11n33b9i"/><path class="xt5xc0eya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:signout" /></template>
