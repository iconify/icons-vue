<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7otw-am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tram-rounded" /></template>
<style>
.ar7otw-am {
  fill: currentColor;
  d: path("M5 17.116V8q0-1.829 1.856-2.386T11.462 5l.75-1.5H7.519q-.19 0-.316-.126t-.126-.316t.126-.317t.316-.126h8.962q.19 0 .316.126t.126.317t-.126.316t-.316.126h-3.193l-.75 1.5q2.802.056 4.632.61Q19 6.167 19 8v9.116q0 1.205-.84 2.045q-.839.839-2.044.839l1.192 1.192q.233.233.113.52t-.45.288q-.098 0-.183-.034q-.086-.033-.153-.1L14.769 20H9.231l-1.865 1.866q-.068.067-.153.1q-.086.034-.184.034q-.325 0-.447-.287q-.122-.288.11-.52L7.885 20q-1.206 0-2.045-.84Q5 18.322 5 17.117m7.793.177q.323-.322.323-.793t-.323-.793q-.322-.323-.793-.323t-.793.323q-.323.322-.323.793t.323.793q.322.323.793.323t.793-.323M6 13h12V8.539H6z");
}

</style>
