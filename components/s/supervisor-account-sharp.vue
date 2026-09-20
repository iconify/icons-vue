<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjarxvblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:supervisor-account-sharp" /></template>
<style>
.tjarxvblp {
  fill: currentColor;
  d: path("M2.616 18.616v-1.647q0-.657.357-1.197q.358-.54.973-.799q1.327-.673 2.757-1.015t2.913-.342q.49 0 .98.039q.49.04.981.107v.363q-1.01.762-1.486 1.633q-.475.87-.475 2.013v.844zm9.769 0v-.9q0-.466.235-.844q.236-.378.657-.545q.842-.356 1.747-.534q.905-.177 1.86-.177q.918 0 1.823.177q.905.178 1.785.534q.422.167.657.545t.236.844v.9zm3.09-5.591q-.59-.59-.59-1.41q0-.819.59-1.41q.59-.59 1.41-.59q.819 0 1.41.59q.59.591.59 1.41q0 .82-.59 1.41q-.591.59-1.41.59q-.82 0-1.41-.59m-7.983-2.517q-.876-.877-.876-2.123t.876-2.123t2.124-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.124-.877");
}

</style>
