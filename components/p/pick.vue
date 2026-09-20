<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<g class="gr7bnx5qp"><path class="qity30jlj"/><path class="h1ud42-ch"/></g><path class="pi5jgubhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pick" /></template>
<style>
.gr7bnx5qp {
  fill: var(--svg-color--f4900c, #f4900c);
}

.h1ud42-ch {
  d: path("M3.415 7.657a2 2 0 0 1 0-2.829l1.414-1.414a2 2 0 0 1 2.828 2.829L6.243 7.657a2 2 0 0 1-2.828 0");
}

.pi5jgubhj {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M23 1C21.143.257 12-2 5 5S.257 21.143 1 23c2 5 1.671-1.063 2-3c1.015-5.971 3.822-9.178 5.822-11.178S14.051 4.029 20 3c1.921-.332 8 0 3-2");
}

.qity30jlj {
  d: path("M29.185 33.279c1.166 1.166 3.022 1.221 4.121.121s1.045-2.955-.121-4.121L9.921 6.014C8.754 4.847 6.899 4.792 5.8 5.893c-1.101 1.1-1.046 2.955.121 4.121z");
}

</style>
