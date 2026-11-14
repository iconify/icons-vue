<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy0kviyrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:path-light" /></template>
<style>
.yy0kviyrb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.54 1.908l-4.5 3.5q-.068.053-.122.119q-.054.067-.092.143q-.037.077-.057.161q-.019.083-.019.169q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.826q-.076.337-.076.75v2q0 2.25 2.25 2.25h.75v5.005q-8 .115-8 2.745q0 2.75 8.75 2.75t8.75-2.75q0-2.63-8-2.745V11.75h.75q2.25 0 2.25-2.25v-2q0-.413-.076-.75h.826q.086 0 .169-.019q.084-.02.161-.057q.076-.038.143-.092t.119-.122q.045-.058.078-.124q.034-.066.053-.137q.02-.071.025-.145t-.004-.147t-.032-.143q-.024-.071-.06-.135q-.037-.064-.085-.12t-.107-.101l-4.5-3.5q-.049-.038-.103-.068q-.055-.029-.114-.049q-.058-.021-.12-.031T12 1.75t-.123.01t-.12.031t-.114.049q-.054.03-.103.068");
}

</style>
